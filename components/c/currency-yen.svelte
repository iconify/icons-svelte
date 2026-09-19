<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2npl7jrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2npl7jrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:currency-yen" {...props}></Icon>
