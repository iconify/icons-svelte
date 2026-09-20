<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcqc0pbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qcqc0pbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:elastic-stack-logo-block" {...props}></Icon>
