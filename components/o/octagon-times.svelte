<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r88yrtzkl.css';
import '../../css/a/al9hzkb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r88yrtzkl"/><path class="al9hzkb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:octagon-times" {...props}></Icon>
