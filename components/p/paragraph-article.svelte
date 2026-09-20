<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm53bibrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vm53bibrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:paragraph-article" {...props}></Icon>
