<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzkb3gzut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzkb3gzut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:person-add-2" {...props}></Icon>
