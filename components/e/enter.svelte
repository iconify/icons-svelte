<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/b/bmyzfebyy.css';
import '../../css/f/f7lhasbpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="bmyzfebyy"/><path class="f7lhasbpb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:enter" {...props}></Icon>
