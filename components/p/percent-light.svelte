<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6wne7bud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6wne7bud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:percent-light" {...props}></Icon>
