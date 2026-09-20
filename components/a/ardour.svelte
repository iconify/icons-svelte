<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa0jrpw7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qa0jrpw7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ardour" {...props}></Icon>
