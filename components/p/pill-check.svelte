<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qircv0fuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qircv0fuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:pill-check" {...props}></Icon>
