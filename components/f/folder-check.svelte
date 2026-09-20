<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/k/k426k8bwo.css';
import '../../css/d/db1ausrdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k426k8bwo"/><path class="db1ausrdr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:folder-check" {...props}></Icon>
