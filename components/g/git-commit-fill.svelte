<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un0416bza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="un0416bza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:git-commit-fill" {...props}></Icon>
