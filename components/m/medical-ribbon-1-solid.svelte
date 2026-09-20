<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-knf-gad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c-knf-gad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:medical-ribbon-1-solid" {...props}></Icon>
