<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edpp-ebii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edpp-ebii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-down-left-dashed-panel-sharp-fill" {...props}></Icon>
