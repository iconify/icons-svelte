<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0gq10n2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="e0gq10n2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-return-filled" {...props}></Icon>
