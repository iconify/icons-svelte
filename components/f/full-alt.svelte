<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilpm5tagc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilpm5tagc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:full-alt" {...props}></Icon>
