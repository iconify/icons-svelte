<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psiglkazx.css';
import '../../css/n/ntlr19bwp.css';
import '../../css/c/c6n323zgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="psiglkazx"><path class="ntlr19bwp"/><path class="c6n323zgn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:cloud-gpu" {...props}></Icon>
