<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5_zu7bdk.css';
import '../../css/e/elcyybcku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGdPdPCXCl" class="f5_zu7bdk"/><path id="SVGXdxzPddm" class="elcyybcku"/></defs><use href="#SVGdPdPCXCl"/><use href="#SVGXdxzPddm"/><use href="#SVGdPdPCXCl"/><use href="#SVGXdxzPddm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:cloud-download-fill" {...props}></Icon>
