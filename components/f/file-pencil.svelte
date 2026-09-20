<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/i/i9nr7ibyg.css';
import '../../css/a/ar_oz7byj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="i9nr7ibyg"/><path class="ar_oz7byj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:file-pencil" {...props}></Icon>
