<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yagq6hbek.css';
import '../../css/f/f6k8znems.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yagq6hbek"/><path class="f6k8znems"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-switch-light" {...props}></Icon>
