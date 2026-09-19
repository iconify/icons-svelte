<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef3cp9bso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="ef3cp9bso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:drupal" {...props}></Icon>
