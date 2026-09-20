<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zaywovj7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zaywovj7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:hand-holding-dollar-solid" {...props}></Icon>
