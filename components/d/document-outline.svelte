<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/t/ti1j9ac6u.css';
import '../../css/i/ixtfyqwbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="document-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="ti1j9ac6u"/><path class="ixtfyqwbi"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:document-outline" {...props}></Icon>
