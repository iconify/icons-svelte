<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmlk55iho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmlk55iho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ikea-fado" {...props}></Icon>
