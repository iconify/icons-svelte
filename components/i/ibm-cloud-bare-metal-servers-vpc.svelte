<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzccu8bfu.css';
import '../../css/v/vjxwbqfru.css';
import '../../css/y/y8mkib1ak.css';
import '../../css/u/un5zkmt9p.css';
import '../../css/m/mhauvu0ld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="jzccu8bfu"/><path class="vjxwbqfru"/><circle class="y8mkib1ak"/><path class="un5zkmt9p"/><path class="mhauvu0ld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-bare-metal-servers-vpc" {...props}></Icon>
