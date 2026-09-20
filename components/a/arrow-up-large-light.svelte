<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb2nzco-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eb2nzco-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:arrow-up-large-light" {...props}></Icon>
