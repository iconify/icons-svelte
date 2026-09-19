<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4so4lb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4so4lb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:lock-open-alt-02-filled" {...props}></Icon>
