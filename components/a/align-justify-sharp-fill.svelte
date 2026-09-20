<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/seccp3txc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="seccp3txc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-justify-sharp-fill" {...props}></Icon>
