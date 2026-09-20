<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw8kuhb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qw8kuhb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:newspaper" {...props}></Icon>
