<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/n/nhyri2ljc.css';
import '../../css/v/vkt7vo9kr.css';
import '../../css/f/fm-vxjbkb.css';
import '../../css/s/s5ai2njpa.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJNCLbeqC"><g class="s9cl3zbei"><path class="nhyri2ljc"/><path class="vkt7vo9kr"/><circle class="fm-vxjbkb"/><circle class="s5ai2njpa"/></g></mask></defs><path mask="url(#SVGJNCLbeqC)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:owl" {...props}></Icon>
