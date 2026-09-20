<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo3t5svif.css';
import '../../css/e/e95pqp9nl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qo3t5svif"/><path class="e95pqp9nl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:creativity-idea-bulb" {...props}></Icon>
