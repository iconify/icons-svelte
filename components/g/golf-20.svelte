<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md4nzgbup.css';
import '../../css/e/e41hepbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="md4nzgbup"/><path class="e41hepbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:golf-20" {...props}></Icon>
