<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1kfdbb0u.css';
import '../../css/l/lieqa6bpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="q1kfdbb0u"/><path class="lieqa6bpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:img-fill" {...props}></Icon>
