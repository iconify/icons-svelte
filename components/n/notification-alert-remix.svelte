<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5umu2byg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="o5umu2byg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:notification-alert-remix" {...props}></Icon>
