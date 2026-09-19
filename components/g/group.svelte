<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3y9k2i2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3y9k2i2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:group" {...props}></Icon>
