<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k788n-8wd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k788n-8wd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:cloud-lightning" {...props}></Icon>
