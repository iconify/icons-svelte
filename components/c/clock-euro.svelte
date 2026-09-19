<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgcm-dbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgcm-dbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:clock-euro" {...props}></Icon>
