<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/d/dqolircih.css';
import '../../css/z/z8g2jgblp.css';
import '../../css/f/fggvvekwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="dqolircih"/><path class="z8g2jgblp"/><circle class="fggvvekwy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:divide" {...props}></Icon>
