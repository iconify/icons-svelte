<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmbn4-8qw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="lmbn4-8qw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:crop" {...props}></Icon>
