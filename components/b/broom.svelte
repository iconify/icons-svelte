<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcs9q456l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mcs9q456l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:broom" {...props}></Icon>
