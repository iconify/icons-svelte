<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvq0zfibe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dvq0zfibe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:briefcase" {...props}></Icon>
