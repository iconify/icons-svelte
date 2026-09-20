<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtp0xqp4x.css';
import '../../css/j/j3n2vbcov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dtp0xqp4x"/><path class="j3n2vbcov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:check-circle" {...props}></Icon>
