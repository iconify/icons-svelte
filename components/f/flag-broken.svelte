<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9pkbqaxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9pkbqaxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:flag-broken" {...props}></Icon>
