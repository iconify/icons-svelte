<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usgsh8fjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usgsh8fjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrows-rotate" {...props}></Icon>
