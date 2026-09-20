<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqr0i-kdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqr0i-kdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:longhorn" {...props}></Icon>
