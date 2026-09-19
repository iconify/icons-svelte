<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmwojzuep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmwojzuep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:briefcase-alt-filled" {...props}></Icon>
