<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqo0nyghb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqo0nyghb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:arrow-up-right" {...props}></Icon>
