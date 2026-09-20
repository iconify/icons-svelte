<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dykvwujvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dykvwujvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-standing-wearing-dress-beside-child-standing-beside-broadshouldered-person-standing" {...props}></Icon>
