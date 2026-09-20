<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9x4iebyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9x4iebyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:git-pull-request-draft-24" {...props}></Icon>
