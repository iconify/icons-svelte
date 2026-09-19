<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2_ie9n9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":371,"height":512};
const content = `<path clip-rule="evenodd" class="b2_ie9n9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:coreldraw-alt" {...props}></Icon>
