<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/y/y3bs4jbfx.css';
import '../../css/q/qknhedbtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="edit-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="y3bs4jbfx"/><path class="qknhedbtq"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:edit-outline" {...props}></Icon>
