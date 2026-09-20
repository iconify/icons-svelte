<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7599ebdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7599ebdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:merge" {...props}></Icon>
