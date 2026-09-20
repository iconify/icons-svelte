<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qli8pklap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qli8pklap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:pump" {...props}></Icon>
