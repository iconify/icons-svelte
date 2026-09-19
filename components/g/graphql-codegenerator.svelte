<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsa3t6fnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":393,"height":512};
const content = `<path class="rsa3t6fnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:graphql-codegenerator" {...props}></Icon>
