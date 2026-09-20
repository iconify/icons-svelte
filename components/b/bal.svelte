<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it4o-9bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="it4o-9bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bal" {...props}></Icon>
