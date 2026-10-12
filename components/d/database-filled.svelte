<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq1yx56sg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rq1yx56sg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:database-filled" {...props}></Icon>
