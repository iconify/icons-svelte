<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqbik8bfl.css';
import '../../css/y/y3bjwfy8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="eqbik8bfl"/><path class="y3bjwfy8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-outpatient" {...props}></Icon>
