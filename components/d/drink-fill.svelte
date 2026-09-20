<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5lkd49ak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h5lkd49ak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:drink-fill" {...props}></Icon>
