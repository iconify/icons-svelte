<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx668v65z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tx668v65z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:book4-filled" {...props}></Icon>
