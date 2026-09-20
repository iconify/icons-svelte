<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayom0ebyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ayom0ebyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:git-pull-request-create-arrow" {...props}></Icon>
