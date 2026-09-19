<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnhwl-37f.css';
import '../../css/i/ipmkijbyf.css';
import '../../css/x/xsojoj1yq.css';
import '../../css/k/kai3f3bib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mnhwl-37f"/><path class="ipmkijbyf"/><path class="xsojoj1yq"/><path class="kai3f3bib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:honeybee" {...props}></Icon>
