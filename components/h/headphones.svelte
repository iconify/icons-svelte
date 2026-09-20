<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6kfg4k8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d6kfg4k8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:headphones" {...props}></Icon>
