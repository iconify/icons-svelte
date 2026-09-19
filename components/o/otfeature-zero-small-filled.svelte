<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sebvhx9qb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="sebvhx9qb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:otfeature-zero-small-filled" {...props}></Icon>
