<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4z2qobvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o4z2qobvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:curly-brackets-lock" {...props}></Icon>
