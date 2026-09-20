<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qane7acao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qane7acao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:dropbox" {...props}></Icon>
