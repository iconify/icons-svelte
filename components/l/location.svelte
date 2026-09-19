<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v89fl4bla.css';
import '../../css/o/o4cgy6nli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="v89fl4bla"/><path class="o4cgy6nli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:location" {...props}></Icon>
