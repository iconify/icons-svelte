<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1kfg9b6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n1kfg9b6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:badge-check" {...props}></Icon>
