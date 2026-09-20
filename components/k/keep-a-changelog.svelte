<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngda-7gsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngda-7gsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:keep-a-changelog" {...props}></Icon>
