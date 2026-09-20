<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye2s1-byy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ye2s1-byy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:dots-filled" {...props}></Icon>
