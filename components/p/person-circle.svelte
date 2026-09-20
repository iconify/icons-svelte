<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8za1g3zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8za1g3zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:person-circle" {...props}></Icon>
