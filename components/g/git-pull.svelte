<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/o/og_9js9al.css';
import '../../css/t/tke4h5b0x.css';
import '../../css/x/xjh3njbok.css';
import '../../css/a/abae1i7ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="og_9js9al"/><circle class="tke4h5b0x"/><circle class="xjh3njbok"/><path class="abae1i7ne"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:git-pull" {...props}></Icon>
