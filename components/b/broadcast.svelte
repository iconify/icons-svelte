<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn2us-vvy.css';
import '../../css/y/y-9gdnm7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qn2us-vvy"/><path class="y-9gdnm7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:broadcast" {...props}></Icon>
