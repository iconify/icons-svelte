<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz1nq5bbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hz1nq5bbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hashicorp-vagrant-dark" {...props}></Icon>
