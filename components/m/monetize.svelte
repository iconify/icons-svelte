<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aochvebhn.css';
import '../../css/k/kxy6kzbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aochvebhn"/><path class="kxy6kzbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:monetize" {...props}></Icon>
