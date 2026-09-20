<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_ezh736y.css';
import '../../css/w/wtxugid0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_ezh736y"/><path class="wtxugid0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:cloud-check-light" {...props}></Icon>
