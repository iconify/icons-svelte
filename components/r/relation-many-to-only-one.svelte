<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwqyzxbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwqyzxbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:relation-many-to-only-one" {...props}></Icon>
