<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-02zwb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-02zwb4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:currency-won" {...props}></Icon>
