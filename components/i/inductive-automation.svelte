<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt2q9zboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bt2q9zboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:inductive-automation" {...props}></Icon>
