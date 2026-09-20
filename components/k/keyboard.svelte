<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrekjjbvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrekjjbvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:keyboard" {...props}></Icon>
