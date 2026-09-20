<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxt9i1bsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxt9i1bsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:car-suspension" {...props}></Icon>
