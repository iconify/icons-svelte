<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmn--yb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jmn--yb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:link-broken" {...props}></Icon>
