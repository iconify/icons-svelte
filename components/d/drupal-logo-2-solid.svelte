<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr44hdc3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pr44hdc3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:drupal-logo-2-solid" {...props}></Icon>
