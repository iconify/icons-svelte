<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq-45abkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bq-45abkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:folder-download" {...props}></Icon>
