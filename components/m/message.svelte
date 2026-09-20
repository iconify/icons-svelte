<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etl64wbvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etl64wbvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:message" {...props}></Icon>
