<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbwz4ccyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbwz4ccyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:arrow-right" {...props}></Icon>
