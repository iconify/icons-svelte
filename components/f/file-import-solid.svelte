<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayoxpmbui.css';
import '../../css/e/ex6n6ltjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ayoxpmbui"/><path class="ex6n6ltjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:file-import-solid" {...props}></Icon>
