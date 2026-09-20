<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eirz4gl8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eirz4gl8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-u-turn-right-fill" {...props}></Icon>
