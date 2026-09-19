<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/a/ax3qas8uv.css';
import '../../css/f/fmlca6ojk.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGyEcOuHYh"><g class="wwvp95byt"><path class="ax3qas8uv"/><path clip-rule="evenodd" class="fmlca6ojk"/></g></mask></defs><path mask="url(#SVGyEcOuHYh)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:damage-map" {...props}></Icon>
