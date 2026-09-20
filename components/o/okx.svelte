<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye-7s2bkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ye-7s2bkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:okx" {...props}></Icon>
