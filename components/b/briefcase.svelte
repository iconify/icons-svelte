<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqxw4t2sy.css';
import '../../css/i/iq2exjbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer hqxw4t2sy"/><path class="duoicon-primary-layer iq2exjbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:briefcase" {...props}></Icon>
