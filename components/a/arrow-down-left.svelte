<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erlrlxjjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="erlrlxjjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:arrow-down-left" {...props}></Icon>
