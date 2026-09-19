<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/g/g47cb4b4t.css';
import '../../css/r/r6vob4b7a.css';
import '../../css/o/o-smjjrei.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGcGTQPebU"><g class="ufeehvblu"><rect class="g47cb4b4t"/><path class="r6vob4b7a"/><path class="o-smjjrei"/></g></mask></defs><path mask="url(#SVGcGTQPebU)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:margin-one" {...props}></Icon>
