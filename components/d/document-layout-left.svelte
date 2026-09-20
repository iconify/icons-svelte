<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9qc58bsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9qc58bsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:document-layout-left" {...props}></Icon>
