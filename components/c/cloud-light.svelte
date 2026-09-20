<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_ezh736y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_ezh736y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:cloud-light" {...props}></Icon>
