<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3s29yqba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="s3s29yqba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:dropbox-solid" {...props}></Icon>
