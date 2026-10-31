<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbk-l7bpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbk-l7bpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:asterisk-round" {...props}></Icon>
