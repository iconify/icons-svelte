<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr33f7nqp.css';
import '../../css/a/afu1s7q2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jr33f7nqp"/><path class="afu1s7q2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:arweave" {...props}></Icon>
