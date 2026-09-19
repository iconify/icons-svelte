<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/o/o51294bng.css';
import '../../css/s/sey112v-v.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGxuCMgbns"><g class="ufeehvblu"><path class="o51294bng"/><path class="sey112v-v"/></g></mask></defs><path mask="url(#SVGxuCMgbns)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:document-folder" {...props}></Icon>
