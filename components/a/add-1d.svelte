<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bee52pb2u.css';
import '../../css/y/yl1bn7evw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="bee52pb2u"/><path class="yl1bn7evw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:add-1d" {...props}></Icon>
