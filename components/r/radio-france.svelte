<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fse-8sbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fse-8sbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:radio-france" {...props}></Icon>
