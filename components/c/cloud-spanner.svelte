<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/d/dn5myfbwf.css';
import '../../css/c/ca5a0rbuv.css';
import '../../css/s/sltux9jbj.css';
import '../../css/s/s-dq4inme.css';
import '../../css/s/sij6f2sib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="dn5myfbwf"/><path class="ca5a0rbuv"/><path class="sltux9jbj"/><path class="s-dq4inme"/><path class="sij6f2sib"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:cloud-spanner" {...props}></Icon>
