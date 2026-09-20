<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qel0gob0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qel0gob0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:expand-vertical-solid" {...props}></Icon>
