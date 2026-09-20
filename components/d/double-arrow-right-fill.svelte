<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/u/uosmzvb2v.css';
import '../../css/y/y9ynqipcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="uosmzvb2v"/><path class="y9ynqipcp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:double-arrow-right-fill" {...props}></Icon>
