<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgp00ubed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hgp00ubed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:mail-notification-remix" {...props}></Icon>
